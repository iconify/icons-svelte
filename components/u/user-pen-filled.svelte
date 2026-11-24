<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5oq16eap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5oq16eap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-pen-filled" {...props}></Icon>
