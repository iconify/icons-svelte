<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dka9-7apg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dka9-7apg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shopping-bag" {...props}></Icon>
