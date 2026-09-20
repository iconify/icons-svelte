<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fza5vnbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fza5vnbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tile-caution-heavy" {...props}></Icon>
