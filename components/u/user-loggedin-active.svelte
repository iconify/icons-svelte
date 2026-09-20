<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u89970-3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u89970-3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:user-loggedin-active" {...props}></Icon>
