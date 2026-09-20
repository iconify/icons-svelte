<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_aev9b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l_aev9b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:wifi-antenna-remix" {...props}></Icon>
