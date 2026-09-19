<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a103id3vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a103id3vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:text-stroke-12" {...props}></Icon>
