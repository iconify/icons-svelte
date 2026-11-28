<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ady5bhbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ady5bhbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tag-star" {...props}></Icon>
