<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm7__ybvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm7__ybvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:table-plus" {...props}></Icon>
