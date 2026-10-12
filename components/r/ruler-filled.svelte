<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqezmi50p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqezmi50p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ruler-filled" {...props}></Icon>
