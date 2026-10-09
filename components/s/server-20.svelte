<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eab-bra5j.css';
import '../../css/e/eokgyxb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eab-bra5j"/><path class="eokgyxb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:server-20" {...props}></Icon>
