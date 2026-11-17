<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo3ie7blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xo3ie7blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:stroke-line-cap-round-filled" {...props}></Icon>
