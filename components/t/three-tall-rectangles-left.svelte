<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7z0dvb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b7z0dvb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-tall-rectangles-left" {...props}></Icon>
