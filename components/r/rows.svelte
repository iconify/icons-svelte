<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax4b43b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax4b43b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:rows" {...props}></Icon>
