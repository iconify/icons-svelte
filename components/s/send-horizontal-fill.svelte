<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5syz5bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5syz5bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:send-horizontal-fill" {...props}></Icon>
