<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpn0yibgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tpn0yibgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:text-flow-rows-remix" {...props}></Icon>
