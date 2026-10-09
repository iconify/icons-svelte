<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5y_4mbdq.css';
import '../../css/g/gdcg3vxtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a5y_4mbdq"/><path class="gdcg3vxtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-bottle-48-bold" {...props}></Icon>
