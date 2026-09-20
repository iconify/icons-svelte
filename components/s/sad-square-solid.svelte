<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js4f3kb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js4f3kb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:sad-square-solid" {...props}></Icon>
