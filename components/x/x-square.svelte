<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocij7pajl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocij7pajl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:x-square" {...props}></Icon>
