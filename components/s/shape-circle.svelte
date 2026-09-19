<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh27ejb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh27ejb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:shape-circle" {...props}></Icon>
