<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6hu3abep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6hu3abep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowman-fill" {...props}></Icon>
