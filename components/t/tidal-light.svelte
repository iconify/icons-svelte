<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d59vkeb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1001,"height":667};
const content = `<path class="d59vkeb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tidal-light" {...props}></Icon>
