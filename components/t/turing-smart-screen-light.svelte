<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_j005jqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k_j005jqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:turing-smart-screen-light" {...props}></Icon>
