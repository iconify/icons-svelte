<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9r54cbek.css';
import '../../css/w/wsm_8oqcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9r54cbek"/><path class="wsm_8oqcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:showers-fill" {...props}></Icon>
