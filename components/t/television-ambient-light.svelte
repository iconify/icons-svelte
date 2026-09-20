<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxfgj3bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxfgj3bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:television-ambient-light" {...props}></Icon>
