<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl_57ib0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="hl_57ib0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-js" {...props}></Icon>
