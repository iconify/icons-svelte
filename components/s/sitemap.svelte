<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bakgywbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="bakgywbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:sitemap" {...props}></Icon>
