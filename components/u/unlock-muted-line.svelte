<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uom6yvocs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uom6yvocs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:unlock-muted-line" {...props}></Icon>
