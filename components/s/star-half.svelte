<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcpdy7bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="dcpdy7bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:star-half" {...props}></Icon>
