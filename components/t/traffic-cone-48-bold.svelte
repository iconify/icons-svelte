<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe1o59byh.css';
import '../../css/a/anawxhbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pe1o59byh"/><path class="anawxhbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:traffic-cone-48-bold" {...props}></Icon>
