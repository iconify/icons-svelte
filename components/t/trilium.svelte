<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewzfa94-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewzfa94-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trilium" {...props}></Icon>
