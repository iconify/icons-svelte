<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7kxs01qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7kxs01qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sigma-duo" {...props}></Icon>
