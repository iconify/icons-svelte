<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu4izou2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hu4izou2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:users-48" {...props}></Icon>
