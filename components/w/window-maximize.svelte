<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6laare-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d6laare-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:window-maximize" {...props}></Icon>
