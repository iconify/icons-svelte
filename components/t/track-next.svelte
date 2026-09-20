<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6bnuccvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z6bnuccvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:track-next" {...props}></Icon>
