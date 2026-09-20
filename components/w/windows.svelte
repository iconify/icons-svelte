<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpiizxoqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpiizxoqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:windows" {...props}></Icon>
