<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq83v1bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tq83v1bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:warning-diamond-fill" {...props}></Icon>
