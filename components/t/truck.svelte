<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izsy9-bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izsy9-bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:truck" {...props}></Icon>
