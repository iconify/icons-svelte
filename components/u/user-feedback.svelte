<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9xfwac2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f9xfwac2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-feedback" {...props}></Icon>
