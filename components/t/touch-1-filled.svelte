<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq__i_bat.css';
import '../../css/l/lpad86zwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lq__i_bat"/><path class="lpad86zwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:touch-1-filled" {...props}></Icon>
