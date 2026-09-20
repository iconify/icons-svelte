<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxo0sinma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxo0sinma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:sketch" {...props}></Icon>
