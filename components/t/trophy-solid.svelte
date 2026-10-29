<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhgnyvphq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhgnyvphq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trophy-solid" {...props}></Icon>
