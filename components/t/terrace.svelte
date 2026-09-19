<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvj62rbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvj62rbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:terrace" {...props}></Icon>
