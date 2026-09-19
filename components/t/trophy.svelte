<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqph7n_sh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rqph7n_sh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:trophy" {...props}></Icon>
