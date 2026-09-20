<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq-co7oys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zq-co7oys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:subscript-solid" {...props}></Icon>
