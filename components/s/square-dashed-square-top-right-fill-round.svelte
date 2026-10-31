<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks_mkebyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks_mkebyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dashed-square-top-right-fill-round" {...props}></Icon>
