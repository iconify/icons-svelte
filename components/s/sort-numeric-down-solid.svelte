<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltwtj0gsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ltwtj0gsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sort-numeric-down-solid" {...props}></Icon>
