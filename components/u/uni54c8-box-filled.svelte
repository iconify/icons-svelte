<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdqkzx6-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xdqkzx6-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni54c8-box-filled" {...props}></Icon>
