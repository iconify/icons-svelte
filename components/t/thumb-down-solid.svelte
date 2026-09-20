<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3epd7bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i3epd7bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:thumb-down-solid" {...props}></Icon>
