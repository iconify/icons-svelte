<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpf9e5ula.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpf9e5ula"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:shutter-90" {...props}></Icon>
