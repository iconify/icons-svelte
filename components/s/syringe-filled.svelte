<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn1gikdgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn1gikdgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:syringe-filled" {...props}></Icon>
