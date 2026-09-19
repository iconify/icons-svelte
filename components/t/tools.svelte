<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqi1k2b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31.87,"height":32};
const content = `<path class="lqi1k2b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:tools" {...props}></Icon>
