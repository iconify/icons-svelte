<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwbh7nbys.css';
import '../../css/z/zbgf9zo9k.css';
import '../../css/d/dfp9on1-c.css';
import '../../css/b/blnr7rb1l.css';
import '../../css/w/w4cknsjdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gwbh7nbys"/><path class="zbgf9zo9k"/><path class="dfp9on1-c"/><path class="blnr7rb1l"/><path class="w4cknsjdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:tauri-wordmark" {...props}></Icon>
