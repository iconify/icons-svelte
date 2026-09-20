<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbbpg3bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2};
const content = `<path class="wbbpg3bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:vine" {...props}></Icon>
