<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xab97jbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xab97jbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:underline-a" {...props}></Icon>
