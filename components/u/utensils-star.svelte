<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noiu_naty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="noiu_naty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:utensils-star" {...props}></Icon>
