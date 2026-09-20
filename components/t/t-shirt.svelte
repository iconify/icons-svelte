<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uez0nrb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="uez0nrb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:t-shirt" {...props}></Icon>
