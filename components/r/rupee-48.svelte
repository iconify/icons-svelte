<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2mz6fbaj.css';
import '../../css/l/loq84tx7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j2mz6fbaj"/><path class="loq84tx7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rupee-48" {...props}></Icon>
