<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrpvxrlxf.css';
import '../../css/b/bxzxb8v8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vrpvxrlxf"/><path class="bxzxb8v8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-alert-48" {...props}></Icon>
