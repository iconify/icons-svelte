<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htzdpg-mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htzdpg-mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:two-diamond-solid" {...props}></Icon>
