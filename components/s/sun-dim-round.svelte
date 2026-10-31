<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dku-ycbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dku-ycbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sun-dim-round" {...props}></Icon>
