<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9fh_quic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9fh_quic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:xing" {...props}></Icon>
