<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_v2-7tnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t_v2-7tnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:shopping-basket-2-remix" {...props}></Icon>
