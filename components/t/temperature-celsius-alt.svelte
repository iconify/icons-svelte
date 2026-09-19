<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq6e4izvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xq6e4izvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:temperature-celsius-alt" {...props}></Icon>
