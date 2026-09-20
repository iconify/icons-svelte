<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-d7b5o7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-d7b5o7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:webcam-solid" {...props}></Icon>
