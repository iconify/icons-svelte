<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovc-odbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ovc-odbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tidal-dark" {...props}></Icon>
