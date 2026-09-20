<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqfh6jc-b.css';
import '../../css/q/q7imqmbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqfh6jc-b"/><path class="q7imqmbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:vintage-tv-1" {...props}></Icon>
