<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v945mrjcg.css';
import '../../css/l/l2m0plbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v945mrjcg"/><path class="l2m0plbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sparkline-20-bold" {...props}></Icon>
