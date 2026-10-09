<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1wr267gl.css';
import '../../css/z/zq8n3hqfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m1wr267gl"/><path class="zq8n3hqfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tent-48-bold" {...props}></Icon>
