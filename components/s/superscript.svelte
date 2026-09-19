<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycjdik35z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycjdik35z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:superscript" {...props}></Icon>
