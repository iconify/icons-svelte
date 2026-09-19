<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccydevo3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ccydevo3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:slot-machine" {...props}></Icon>
