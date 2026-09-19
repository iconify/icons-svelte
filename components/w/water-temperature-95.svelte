<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5r4nqb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":448};
const content = `<path class="l5r4nqb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:water-temperature-95" {...props}></Icon>
