<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hob83lbft.css';
import '../../css/l/lhdxw8u5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hob83lbft"/><path class="lhdxw8u5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tablet-20" {...props}></Icon>
