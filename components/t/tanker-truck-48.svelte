<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m35bxhbui.css';
import '../../css/q/q0uyhzb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m35bxhbui"/><path class="q0uyhzb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tanker-truck-48" {...props}></Icon>
