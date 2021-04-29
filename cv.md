# Siarhei Lysiuk


 ## CONTACT INFO

 ### Home: Minsk, Belarus

 ### Phone: + 375 33 685 23 15

 ### e-mail: sergei.lysiuk@gmail.com
 
 ### linkedin: https://www.linkedin.com/in/sergei-lysiuk-46656189/
 

## SUMMARY

### Team Lead, iOS Mobile
 Mart 2019 -  now
- management of a team of 3-5 developers
- making key decisions on the architecture of projects
- creation and sharing of external libraries to connect to two or more projects
- participation in the development of client-server models
- writing and checking code

### iOS Developer
May 2014 -  Mart 2019 
- developing Client/Server Applications
- correction and integration of cross-platform SVG library for iOS (C++/C)
- maintaining and developing applications
- correcting errors in the game and work with OpenGL ES


## SKILLS

- Programming: Swift, Objective C, C#, C++
- GIT, Bitbucket, Trello, Xcode, Visual  Studio, Silk Test

## CODE EXAMPLE

public protocol RouterProtocol: AnyObject {
    init(navigationService: NavigationServiceProtocol, flow: FlowProtocol?)
    func showViewModel<T: ViewModelProtocol>(_ type: T.Type, with: ParameterProtocol?, flow: FlowProtocol?, completion: Action?)
    func showViewModel<T: ViewModelProtocol>(_ type: T, with: ParameterProtocol?, flow: FlowProtocol?, completion: Action?)
    func present<T: ViewModelProtocol>(viewModel: T.Type, with: ParameterProtocol?, flow: FlowProtocol?, style: PresentationStyle, completion: Action?)
    func presentService<T: ViewModelProtocol>(viewModel: T.Type, with: ParameterProtocol?, flow: FlowProtocol?, style: PresentationStyle, animated: Bool, completion: Action?)
    func closePresented(completion: Action?, animated: Bool)

    func close<T: ViewModelProtocol>(_ : T, completion: Action?)
    func remove<T: ViewModelProtocol>(_ : T)
    func remove<T: ViewModelProtocol>(_ : T.Type)

    func next<T: BaseViewModel>(_ : T, with: ParameterProtocol?)
    func breakFlow<T: BaseViewModel>(_ viewModel: T, with data: ParameterProtocol?)
}

