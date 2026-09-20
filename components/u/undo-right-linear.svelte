<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgl7dnbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgl7dnbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-right-linear" {...props}></Icon>
