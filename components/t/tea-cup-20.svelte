<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leutjaccr.css';
import '../../css/k/kogtqeljo.css';
import '../../css/a/av7sw4bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="leutjaccr"/><path class="kogtqeljo"/><path class="av7sw4bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tea-cup-20" {...props}></Icon>
