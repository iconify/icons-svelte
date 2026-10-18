<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj0pjib0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj0pjib0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:ticket" {...props}></Icon>
