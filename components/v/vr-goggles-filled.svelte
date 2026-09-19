<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lijijvxoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lijijvxoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vr-goggles-filled" {...props}></Icon>
