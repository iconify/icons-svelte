<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbce29bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbce29bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-check-filled" {...props}></Icon>
