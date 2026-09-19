<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec4-k7yoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ec4-k7yoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:spreadsheet" {...props}></Icon>
