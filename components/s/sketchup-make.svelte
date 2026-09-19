<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-1edmnsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":475,"height":512};
const content = `<path class="o-1edmnsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:sketchup-make" {...props}></Icon>
