<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no77hrbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="no77hrbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:trash" {...props}></Icon>
