<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_80r7goz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_80r7goz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:technology" {...props}></Icon>
