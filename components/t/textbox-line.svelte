<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxc0_evgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxc0_evgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:textbox-line" {...props}></Icon>
