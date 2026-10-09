<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu0uvqb2l.css';
import '../../css/k/kafchl2bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fu0uvqb2l"/><path class="kafchl2bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tv-48" {...props}></Icon>
