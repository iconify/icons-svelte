<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly4hycbgl.css';
import '../../css/c/cle0u0bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly4hycbgl"/><path class="cle0u0bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:terminal-24" {...props}></Icon>
