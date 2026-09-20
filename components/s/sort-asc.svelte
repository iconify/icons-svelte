<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_229_bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_229_bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sort-asc" {...props}></Icon>
