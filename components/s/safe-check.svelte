<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj4xmrbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj4xmrbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:safe-check" {...props}></Icon>
