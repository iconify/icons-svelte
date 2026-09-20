<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo56o1kxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo56o1kxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-hide-fill" {...props}></Icon>
