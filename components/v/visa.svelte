<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cury92biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":24};
const content = `<path class="cury92biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:visa" {...props}></Icon>
