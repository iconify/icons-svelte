<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi1_j4h9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="gi1_j4h9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:shopping-basket" {...props}></Icon>
