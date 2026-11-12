<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvyne8bgw.css';
import '../../css/z/zeqclcbxs.css';
import '../../css/i/ipw49hbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qvyne8bgw"/><path class="zeqclcbxs"/><path class="ipw49hbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:taskade-wordmark" {...props}></Icon>
