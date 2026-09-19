<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs0zpe4kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zs0zpe4kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:storyist" {...props}></Icon>
