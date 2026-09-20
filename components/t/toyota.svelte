<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huv7wf-bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huv7wf-bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:toyota" {...props}></Icon>
