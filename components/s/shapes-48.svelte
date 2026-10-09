<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oobt_dbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oobt_dbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shapes-48" {...props}></Icon>
