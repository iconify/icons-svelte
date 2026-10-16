<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moyoz5fkv.css';
import '../../css/f/fe7lf8b9s.css';
import '../../css/f/fcqcyrnly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="moyoz5fkv"/><path class="fe7lf8b9s"/><path class="fcqcyrnly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:steering-wheel-48-bold" {...props}></Icon>
