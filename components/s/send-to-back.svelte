<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2m872bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2m872bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:send-to-back" {...props}></Icon>
