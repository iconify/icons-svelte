<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9_hs9kxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m9_hs9kxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-text-filled" {...props}></Icon>
