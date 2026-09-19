<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do17ynreu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="do17ynreu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:warning-compact" {...props}></Icon>
