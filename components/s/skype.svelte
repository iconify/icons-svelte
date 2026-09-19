<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_9297i3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="h_9297i3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:skype" {...props}></Icon>
