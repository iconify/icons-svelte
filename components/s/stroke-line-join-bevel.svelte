<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv898niqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv898niqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:stroke-line-join-bevel" {...props}></Icon>
