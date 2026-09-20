<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd13973hj.css';
import '../../css/g/gu_5xob7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd13973hj"/><path class="gu_5xob7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:wifi-signal-4-bold" {...props}></Icon>
