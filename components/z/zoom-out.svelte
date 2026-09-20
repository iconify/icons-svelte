<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eunpcrb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eunpcrb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:zoom-out" {...props}></Icon>
