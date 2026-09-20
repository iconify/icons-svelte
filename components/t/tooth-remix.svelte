<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir_rxsbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ir_rxsbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:tooth-remix" {...props}></Icon>
