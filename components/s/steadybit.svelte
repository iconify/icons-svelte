<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knz28iicx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knz28iicx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:steadybit" {...props}></Icon>
