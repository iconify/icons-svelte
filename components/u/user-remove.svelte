<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbnj8bycg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbnj8bycg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:user-remove" {...props}></Icon>
