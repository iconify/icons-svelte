<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by3hfac2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="by3hfac2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-admin" {...props}></Icon>
