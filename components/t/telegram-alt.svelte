<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4y3y7xtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4y3y7xtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:telegram-alt" {...props}></Icon>
