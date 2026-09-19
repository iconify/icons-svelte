<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdzs-wbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tdzs-wbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-superscript" {...props}></Icon>
