<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eif6ntbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eif6ntbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:twitter-fill-16" {...props}></Icon>
