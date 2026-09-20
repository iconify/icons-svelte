<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf54abxwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gf54abxwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:vectors-path-flat" {...props}></Icon>
