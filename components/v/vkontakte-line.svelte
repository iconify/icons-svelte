<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruwzk5v4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruwzk5v4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vkontakte-line" {...props}></Icon>
