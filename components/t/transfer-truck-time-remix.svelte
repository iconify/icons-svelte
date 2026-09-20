<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkh6_1xxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jkh6_1xxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:transfer-truck-time-remix" {...props}></Icon>
