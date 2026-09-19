<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn3v8nbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tn3v8nbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:ruler-vertical" {...props}></Icon>
