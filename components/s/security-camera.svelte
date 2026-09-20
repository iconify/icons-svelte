<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arbt2q4zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="arbt2q4zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:security-camera" {...props}></Icon>
