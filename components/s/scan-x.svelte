<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo3lo3bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lo3lo3bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:scan-x" {...props}></Icon>
