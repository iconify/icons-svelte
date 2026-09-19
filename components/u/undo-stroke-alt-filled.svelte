<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twyu62blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twyu62blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:undo-stroke-alt-filled" {...props}></Icon>
