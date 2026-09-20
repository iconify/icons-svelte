<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke4wifbjz.css';
import '../../css/q/qeliok-fz.css';
import '../../css/m/mb-jqwb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ke4wifbjz"/><path class="qeliok-fz"/><path class="mb-jqwb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:tune" {...props}></Icon>
