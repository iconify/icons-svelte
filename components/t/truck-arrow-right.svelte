<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buyuy3b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buyuy3b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:truck-arrow-right" {...props}></Icon>
