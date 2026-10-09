<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emhcgzbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="emhcgzbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-20" {...props}></Icon>
