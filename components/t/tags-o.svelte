<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vos18ybrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vos18ybrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:tags-o" {...props}></Icon>
