<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qctubmb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qctubmb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:vip-crown-queen-1-bold" {...props}></Icon>
