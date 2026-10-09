<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7054tbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c7054tbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:underline-48-bold" {...props}></Icon>
