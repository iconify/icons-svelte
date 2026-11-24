<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkdj8isek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkdj8isek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:scan-box-filled" {...props}></Icon>
