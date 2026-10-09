<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es8pyblwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="es8pyblwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-minus-48" {...props}></Icon>
