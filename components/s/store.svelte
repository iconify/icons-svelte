<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjwv7hjvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjwv7hjvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:store" {...props}></Icon>
