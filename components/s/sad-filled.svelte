<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzbnmwbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzbnmwbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sad-filled" {...props}></Icon>
