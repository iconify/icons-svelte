<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7svzrqsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x7svzrqsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sort-numeric-up-solid" {...props}></Icon>
