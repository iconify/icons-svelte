<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zenilsb6y.css';
import '../../css/v/veupicb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zenilsb6y"/><path class="veupicb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-parking-off-filled" {...props}></Icon>
