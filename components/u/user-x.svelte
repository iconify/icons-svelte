<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g46yxebiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g46yxebiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:user-x" {...props}></Icon>
