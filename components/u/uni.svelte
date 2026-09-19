<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-j8aozoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r-j8aozoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:uni" {...props}></Icon>
