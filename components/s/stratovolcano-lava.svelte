<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru1stbp4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ru1stbp4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:stratovolcano-lava" {...props}></Icon>
