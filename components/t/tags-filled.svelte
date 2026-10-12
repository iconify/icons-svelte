<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3is4ubde.css';
import '../../css/h/h7aotvbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3is4ubde"/><path clip-rule="evenodd" class="h7aotvbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tags-filled" {...props}></Icon>
