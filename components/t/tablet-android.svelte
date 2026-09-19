<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq5-1l2ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fq5-1l2ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tablet-android" {...props}></Icon>
