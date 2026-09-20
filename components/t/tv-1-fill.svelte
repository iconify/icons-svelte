<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thwt89bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="thwt89bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tv-1-fill" {...props}></Icon>
