<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-lwp7znm.css';
import '../../css/p/puykbrbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n-lwp7znm"/><path class="puykbrbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tide-low-48-bold" {...props}></Icon>
