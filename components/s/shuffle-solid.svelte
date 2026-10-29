<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elpcvs6hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elpcvs6hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shuffle-solid" {...props}></Icon>
