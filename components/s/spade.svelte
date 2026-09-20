<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4p6gw4td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4p6gw4td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:spade" {...props}></Icon>
