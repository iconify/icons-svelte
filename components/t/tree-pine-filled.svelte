<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxgbzuu-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxgbzuu-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tree-pine-filled" {...props}></Icon>
