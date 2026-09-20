<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aujvfs0gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aujvfs0gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-frame" {...props}></Icon>
