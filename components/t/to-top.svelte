<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0-k71zpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0-k71zpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:to-top" {...props}></Icon>
