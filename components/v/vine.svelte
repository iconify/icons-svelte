<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbibp0bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbibp0bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vine" {...props}></Icon>
