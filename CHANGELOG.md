# Change Log

[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.3.5...HEAD)

**Fixed bugs:**

- v1.3.4 replaced my custom header in open socket? [\#58](https://github.com/WrathChaos/StompClientLib/issues/58)

## [1.3.5](https://github.com/WrathChaos/StompClientLib/tree/1.3.5) (2019-07-25)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.3.4...1.3.5)

**Fixed bugs:**

- StompClientDidConnect not called on a fresh project [\#51](https://github.com/WrathChaos/StompClientLib/issues/51)

**Closed issues:**

- SendJSONForDict error [\#57](https://github.com/WrathChaos/StompClientLib/issues/57)
- Can't connect to websocket with authorization header [\#39](https://github.com/WrathChaos/StompClientLib/issues/39)

**Merged pull requests:**

- \#58 fix open socket with custom header issue [\#59](https://github.com/WrathChaos/StompClientLib/pull/59) ([marain87](https://github.com/marain87))

## [1.3.4](https://github.com/WrathChaos/StompClientLib/tree/1.3.4) (2019-07-19)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.3.3...1.3.4)

## [1.3.3](https://github.com/WrathChaos/StompClientLib/tree/1.3.3) (2019-07-18)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.3.2...1.3.3)

**Closed issues:**

- Missing merge [\#55](https://github.com/WrathChaos/StompClientLib/issues/55)
- Data garbled problem,help [\#41](https://github.com/WrathChaos/StompClientLib/issues/41)

**Merged pull requests:**

- String body parameter and ':'-in-header-value fix [\#56](https://github.com/WrathChaos/StompClientLib/pull/56) ([Erhannis](https://github.com/Erhannis))

## [1.3.2](https://github.com/WrathChaos/StompClientLib/tree/1.3.2) (2019-07-10)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.3.1...1.3.2)

**Implemented enhancements:**

- stompClientWillDisconnect missing [\#44](https://github.com/WrathChaos/StompClientLib/issues/44)

**Merged pull requests:**

- Added 'akaStringBody' parameter to stompClient didReceiveMessage... [\#49](https://github.com/WrathChaos/StompClientLib/pull/49) ([Erhannis](https://github.com/Erhannis))

## [1.3.1](https://github.com/WrathChaos/StompClientLib/tree/1.3.1) (2019-06-14)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.3.0...1.3.1)

**Closed issues:**

- Can I subscribe to multiple topics with one stomp client? [\#47](https://github.com/WrathChaos/StompClientLib/issues/47)
- After subscribing to a topic, how to handle messages from server side? [\#46](https://github.com/WrathChaos/StompClientLib/issues/46)
- socket?.readyState is .OPEN and it never goes to my own "stompClientDidDisconnect" method [\#45](https://github.com/WrathChaos/StompClientLib/issues/45)
- Didconnect function cannot be callback after successful connection [\#43](https://github.com/WrathChaos/StompClientLib/issues/43)
- Login, passcode [\#42](https://github.com/WrathChaos/StompClientLib/issues/42)
- App goes in background lock the kepad the socket disconnected [\#40](https://github.com/WrathChaos/StompClientLib/issues/40)
- stompClientDidConnect not called with Spring boot [\#35](https://github.com/WrathChaos/StompClientLib/issues/35)
- Delegate StompClientDidConnect not called after connect-\>disconnect-\>connect [\#15](https://github.com/WrathChaos/StompClientLib/issues/15)

## [1.3.0](https://github.com/WrathChaos/StompClientLib/tree/1.3.0) (2019-04-30)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.2.7...1.3.0)

**Implemented enhancements:**

- invalidate reconnect [\#36](https://github.com/WrathChaos/StompClientLib/issues/36)

**Closed issues:**

- Should add Carthage [\#33](https://github.com/WrathChaos/StompClientLib/issues/33)
- Invalid Sec-WebSocket-Accept response [\#32](https://github.com/WrathChaos/StompClientLib/issues/32)
- Socket is disconnected with 1007 code as soon as it connected [\#31](https://github.com/WrathChaos/StompClientLib/issues/31)
- enable Assert \(self.readyState != SR\_CONNECTING\) [\#24](https://github.com/WrathChaos/StompClientLib/issues/24)

## [1.2.7](https://github.com/WrathChaos/StompClientLib/tree/1.2.7) (2018-10-23)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.2.6...1.2.7)

## [1.2.6](https://github.com/WrathChaos/StompClientLib/tree/1.2.6) (2018-10-23)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.2.5...1.2.6)

**Fixed bugs:**

- Error when connected to socket [\#23](https://github.com/WrathChaos/StompClientLib/issues/23)

**Closed issues:**

- Auto disconnects [\#11](https://github.com/WrathChaos/StompClientLib/issues/11)

## [1.2.5](https://github.com/WrathChaos/StompClientLib/tree/1.2.5) (2018-10-22)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.2.4...1.2.5)

**Closed issues:**

- Value for "message-id" is always "1" [\#22](https://github.com/WrathChaos/StompClientLib/issues/22)
- Multiple subscription to topics [\#20](https://github.com/WrathChaos/StompClientLib/issues/20)
- I think there is a memory leak for the delegate [\#19](https://github.com/WrathChaos/StompClientLib/issues/19)
- Getting error when framwork is installed in Objective c project [\#9](https://github.com/WrathChaos/StompClientLib/issues/9)

## [1.2.4](https://github.com/WrathChaos/StompClientLib/tree/1.2.4) (2018-10-17)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.2.3...1.2.4)

**Closed issues:**

- didCloseWithCode 1000, reason: nil [\#21](https://github.com/WrathChaos/StompClientLib/issues/21)

## [1.2.3](https://github.com/WrathChaos/StompClientLib/tree/1.2.3) (2018-10-17)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.2.2...1.2.3)

**Implemented enhancements:**

- How to receive heartbeat? [\#18](https://github.com/WrathChaos/StompClientLib/issues/18)

**Closed issues:**

- Socket is not getting connected [\#30](https://github.com/WrathChaos/StompClientLib/issues/30)
- didCloseWithCode 1002 [\#29](https://github.com/WrathChaos/StompClientLib/issues/29)
- No response [\#27](https://github.com/WrathChaos/StompClientLib/issues/27)
- didCloseWithCode 1001, reason: "Stream end encountered" [\#26](https://github.com/WrathChaos/StompClientLib/issues/26)
- Stream end encountered [\#17](https://github.com/WrathChaos/StompClientLib/issues/17)
- unsubscribe socketclient [\#14](https://github.com/WrathChaos/StompClientLib/issues/14)
- It not able to connect web socket. [\#13](https://github.com/WrathChaos/StompClientLib/issues/13)
- One of the delegate method is not being called. [\#12](https://github.com/WrathChaos/StompClientLib/issues/12)
- StompClient Disconnection. [\#10](https://github.com/WrathChaos/StompClientLib/issues/10)
- Unable to find a specification for 'StompClientLib' [\#8](https://github.com/WrathChaos/StompClientLib/issues/8)

## [1.2.2](https://github.com/WrathChaos/StompClientLib/tree/1.2.2) (2017-11-03)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.2.1...1.2.2)

## [1.2.1](https://github.com/WrathChaos/StompClientLib/tree/1.2.1) (2017-10-31)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.2.0...1.2.1)

## [1.2.0](https://github.com/WrathChaos/StompClientLib/tree/1.2.0) (2017-10-29)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.1.7...1.2.0)

**Closed issues:**

- Let client decide what to do with stomp frame body [\#4](https://github.com/WrathChaos/StompClientLib/issues/4)
- Send message support [\#3](https://github.com/WrathChaos/StompClientLib/issues/3)
- Error when calling delegate [\#1](https://github.com/WrathChaos/StompClientLib/issues/1)

## [1.1.7](https://github.com/WrathChaos/StompClientLib/tree/1.1.7) (2017-10-02)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/1.1.6...1.1.7)

## [1.1.6](https://github.com/WrathChaos/StompClientLib/tree/1.1.6) (2017-08-08)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/0.1.5...1.1.6)

## [0.1.5](https://github.com/WrathChaos/StompClientLib/tree/0.1.5) (2017-07-10)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/0.1.4...0.1.5)

## [0.1.4](https://github.com/WrathChaos/StompClientLib/tree/0.1.4) (2017-07-10)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/0.1.3...0.1.4)

## [0.1.3](https://github.com/WrathChaos/StompClientLib/tree/0.1.3) (2017-07-10)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/0.1.2...0.1.3)

## [0.1.2](https://github.com/WrathChaos/StompClientLib/tree/0.1.2) (2017-07-08)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/0.1.1...0.1.2)

## [0.1.1](https://github.com/WrathChaos/StompClientLib/tree/0.1.1) (2017-07-08)
[Full Changelog](https://github.com/WrathChaos/StompClientLib/compare/0.1.0...0.1.1)

## [0.1.0](https://github.com/WrathChaos/StompClientLib/tree/0.1.0) (2017-07-08)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
