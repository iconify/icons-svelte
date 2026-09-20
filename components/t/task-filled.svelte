<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo734ib2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo734ib2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:task-filled" {...props}></Icon>
