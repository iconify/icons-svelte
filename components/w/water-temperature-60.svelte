<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvbaz-blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":448};
const content = `<path class="uvbaz-blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:water-temperature-60" {...props}></Icon>
