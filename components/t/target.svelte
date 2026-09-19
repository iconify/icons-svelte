<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t12n633bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t12n633bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:target" {...props}></Icon>
