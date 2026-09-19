<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooxeae80k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ooxeae80k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:triangle-left-outline" {...props}></Icon>
