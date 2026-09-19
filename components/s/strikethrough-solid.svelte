<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtjx3yi_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vtjx3yi_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:strikethrough-solid" {...props}></Icon>
