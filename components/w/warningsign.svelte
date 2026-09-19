<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeh6a5f4t.css';
import '../../css/a/anpcbdbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yeh6a5f4t"/><path class="anpcbdbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:warningsign" {...props}></Icon>
