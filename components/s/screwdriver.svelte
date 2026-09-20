<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh0h06sep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vh0h06sep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:screwdriver" {...props}></Icon>
