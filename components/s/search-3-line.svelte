<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umi8k7ujp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umi8k7ujp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-3-line" {...props}></Icon>
