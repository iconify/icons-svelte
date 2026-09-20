<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pihu-0nzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pihu-0nzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vitest" {...props}></Icon>
