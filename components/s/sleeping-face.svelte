<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmuh98bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gmuh98bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:sleeping-face" {...props}></Icon>
