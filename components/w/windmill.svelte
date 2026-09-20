<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3pa2wa7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b3pa2wa7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:windmill" {...props}></Icon>
