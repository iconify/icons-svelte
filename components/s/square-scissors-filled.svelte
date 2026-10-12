<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iakgoukpg.css';
import '../../css/p/pabyqgbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iakgoukpg"/><path clip-rule="evenodd" class="pabyqgbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-scissors-filled" {...props}></Icon>
