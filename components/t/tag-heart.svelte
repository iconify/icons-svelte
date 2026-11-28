<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spc51xbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spc51xbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tag-heart" {...props}></Icon>
