<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpjqvnoqu.css';
import '../../css/v/vgkf1kbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wpjqvnoqu"/><path class="vgkf1kbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tab-key-48-bold" {...props}></Icon>
