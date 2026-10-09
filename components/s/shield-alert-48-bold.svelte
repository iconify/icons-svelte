<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4447fbqf.css';
import '../../css/c/c-a3h2bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w4447fbqf"/><path class="c-a3h2bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-alert-48-bold" {...props}></Icon>
