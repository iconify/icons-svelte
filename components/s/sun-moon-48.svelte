<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_hp02zmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e_hp02zmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-moon-48" {...props}></Icon>
