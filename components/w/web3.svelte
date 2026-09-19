<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh34l6hzf.css';
import '../../css/q/qgp7_3b3s.css';
import '../../css/l/lwo1bn0tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wh34l6hzf"/><path class="qgp7_3b3s"/><path class="lwo1bn0tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:web3" {...props}></Icon>
