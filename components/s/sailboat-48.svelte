<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj37yftef.css';
import '../../css/i/i13uryznj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vj37yftef"/><path class="i13uryznj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sailboat-48" {...props}></Icon>
