<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn-_pbbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yn-_pbbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-check-filled" {...props}></Icon>
