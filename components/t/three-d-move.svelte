<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwbksdo8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwbksdo8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:three-d-move" {...props}></Icon>
