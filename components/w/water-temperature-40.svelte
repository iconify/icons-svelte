<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em3iyfb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":448};
const content = `<path class="em3iyfb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:water-temperature-40" {...props}></Icon>
