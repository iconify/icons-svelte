<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqz6vo-oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqz6vo-oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:solar-panel-filled" {...props}></Icon>
