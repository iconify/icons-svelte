<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8450_zvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="m8450_zvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:square-pt" {...props}></Icon>
