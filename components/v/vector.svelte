<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl8hinlhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl8hinlhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:vector" {...props}></Icon>
