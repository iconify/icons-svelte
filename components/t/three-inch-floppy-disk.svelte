<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyb6zf3uf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nyb6zf3uf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-inch-floppy-disk" {...props}></Icon>
