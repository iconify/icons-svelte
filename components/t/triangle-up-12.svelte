<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh-t7_bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wh-t7_bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:triangle-up-12" {...props}></Icon>
