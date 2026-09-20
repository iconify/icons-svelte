<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pffvbac1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pffvbac1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:square-root-alt" {...props}></Icon>
