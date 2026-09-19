<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs37fsenr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qs37fsenr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:xing" {...props}></Icon>
