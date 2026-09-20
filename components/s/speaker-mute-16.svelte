<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-s4f8x0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a-s4f8x0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:speaker-mute-16" {...props}></Icon>
