<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_xk9kz7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e_xk9kz7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:text-dir-ltr" {...props}></Icon>
