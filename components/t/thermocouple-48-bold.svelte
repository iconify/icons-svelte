<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv51c3bzy.css';
import '../../css/h/h09j6xbhq.css';
import '../../css/p/p1u31l47s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nv51c3bzy"/><path class="h09j6xbhq"/><path class="p1u31l47s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermocouple-48-bold" {...props}></Icon>
