<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m899ysyqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m899ysyqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ship" {...props}></Icon>
