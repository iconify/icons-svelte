<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj8vdgbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gj8vdgbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sparkle-fill-20" {...props}></Icon>
