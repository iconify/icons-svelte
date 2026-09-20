<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i42t12bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i42t12bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:volume-low" {...props}></Icon>
