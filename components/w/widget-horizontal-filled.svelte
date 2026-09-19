<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mscblln2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mscblln2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:widget-horizontal-filled" {...props}></Icon>
