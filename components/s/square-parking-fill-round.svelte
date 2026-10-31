<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiey5-55o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiey5-55o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-parking-fill-round" {...props}></Icon>
