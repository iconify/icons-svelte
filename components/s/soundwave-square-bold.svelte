<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yib393y7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yib393y7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:soundwave-square-bold" {...props}></Icon>
