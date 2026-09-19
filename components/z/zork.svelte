<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmvg7-d7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":470,"height":512};
const content = `<path class="qmvg7-d7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:zork" {...props}></Icon>
