<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c78rfib1o.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/j/jyfi0eawb.css';
import '../../css/w/wii29dbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c78rfib1o"/><path class="hwjgqrbah"/><path class="jyfi0eawb"/><path class="wii29dbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-plus-48-bold" {...props}></Icon>
