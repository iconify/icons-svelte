<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so2clvbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="so2clvbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:scissors-open-1-bold" {...props}></Icon>
