<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmrp7wboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lmrp7wboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:y" {...props}></Icon>
