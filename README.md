<img scr= "https://user-images.githubusercontent.com/113047979/215866245-838e7c18-f656-4a98-97ee-341bdcb42ecf.png" />

# Hi, I'm dante franzoi.

<img src="https://github.com/dantefranzoi/dantefranzoi/assets/113047979/d3a61655-f650-4128-933a-147aefedf5a4.png" alt="ilustração de um computador" width="230px" align="right" style="max-width: 100%;">

describe('sobre mim', () => {
  it('sobre mim', () => {
  
    cy.visit('https://www.linkedin.com/in/dantefsantana/')

    cy.contains('Fala pessoa, eu sou o Dante. Sou um aspirante no mundo de QA, além de ser um xereta de desenvolmento web e pesquisador educacional.')
      .should('be.visible')
  })
})
