<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g04p4hb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g04p4hb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:stone-wall-with-battlement" {...props}></Icon>
