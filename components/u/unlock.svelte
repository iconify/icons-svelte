<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4s8bybvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4s8bybvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:unlock" {...props}></Icon>
