<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7cw3xbud.css';
import '../../css/p/pyapzsbgi.css';
import '../../css/m/mo6o3slzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7cw3xbud wm-k"/><path class="pyapzsbgi wm-a"/><path class="mo6o3slzv wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:wind" {...props}></Icon>
