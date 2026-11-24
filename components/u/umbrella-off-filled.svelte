<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9s-_ebbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9s-_ebbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:umbrella-off-filled" {...props}></Icon>
