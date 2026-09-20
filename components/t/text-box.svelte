<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmlm_3bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fmlm_3bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:text-box" {...props}></Icon>
