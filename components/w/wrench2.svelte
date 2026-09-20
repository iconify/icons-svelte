<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avsd8cb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="avsd8cb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:wrench2" {...props}></Icon>
