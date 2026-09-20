<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r34chttoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r34chttoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-by-alpha" {...props}></Icon>
