<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lswb97b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lswb97b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:thermometer" {...props}></Icon>
