<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf502rnmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf502rnmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:triangle-line" {...props}></Icon>
