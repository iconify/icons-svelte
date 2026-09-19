<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdii7hb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zdii7hb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-settings" {...props}></Icon>
