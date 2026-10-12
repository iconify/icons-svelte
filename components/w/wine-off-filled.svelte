<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duq8n_bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duq8n_bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:wine-off-filled" {...props}></Icon>
