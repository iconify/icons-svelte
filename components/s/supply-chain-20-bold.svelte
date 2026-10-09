<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr0p-wb-a.css';
import '../../css/p/pp2amswub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gr0p-wb-a"/><path class="pp2amswub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:supply-chain-20-bold" {...props}></Icon>
