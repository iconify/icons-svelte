<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf351fbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf351fbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wifi-1" {...props}></Icon>
