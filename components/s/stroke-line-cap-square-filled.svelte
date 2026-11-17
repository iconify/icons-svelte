<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jse3np_ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jse3np_ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:stroke-line-cap-square-filled" {...props}></Icon>
