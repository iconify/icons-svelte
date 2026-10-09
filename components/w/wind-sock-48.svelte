<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga00bibxt.css';
import '../../css/u/u1d_hjplu.css';
import '../../css/o/oiqizvb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ga00bibxt"/><path class="u1d_hjplu"/><path class="oiqizvb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-sock-48" {...props}></Icon>
