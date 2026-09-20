<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y30w83bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y30w83bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:temp-hot-line" {...props}></Icon>
