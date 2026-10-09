<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb0jupbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bb0jupbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-moon-48-bold" {...props}></Icon>
