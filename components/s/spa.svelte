<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amb--yjtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amb--yjtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:spa" {...props}></Icon>
