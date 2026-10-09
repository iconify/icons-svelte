<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c78rfib1o.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/u/u9s9akrzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c78rfib1o"/><path class="hwjgqrbah"/><path class="u9s9akrzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-alert-48-bold" {...props}></Icon>
