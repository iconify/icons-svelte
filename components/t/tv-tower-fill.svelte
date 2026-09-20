<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek0np0bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ek0np0bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tv-tower-fill" {...props}></Icon>
