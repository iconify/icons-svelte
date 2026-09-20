<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-q5-nbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a-q5-nbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:vihara" {...props}></Icon>
