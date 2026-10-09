<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnjcr8b9t.css';
import '../../css/z/z6drtmbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cnjcr8b9t"/><path class="z6drtmbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-inverter-48-bold" {...props}></Icon>
