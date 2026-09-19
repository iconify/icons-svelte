<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itl9s5g-p.css';
import '../../css/z/z6pxdsb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itl9s5g-p"/><path class="z6pxdsb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:spa-filled" {...props}></Icon>
