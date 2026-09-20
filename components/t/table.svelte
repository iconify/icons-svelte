<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f65bd6b3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f65bd6b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:table" {...props}></Icon>
