<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooqpa4igp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ooqpa4igp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-rose-48" {...props}></Icon>
