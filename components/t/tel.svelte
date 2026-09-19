<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfmi2obmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qfmi2obmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:tel" {...props}></Icon>
