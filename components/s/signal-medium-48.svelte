<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3dr6cpiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w3dr6cpiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signal-medium-48" {...props}></Icon>
