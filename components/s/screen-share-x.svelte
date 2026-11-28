<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc_3m-lqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc_3m-lqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:screen-share-x" {...props}></Icon>
