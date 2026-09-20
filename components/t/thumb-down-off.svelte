<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kge1oi_wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kge1oi_wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:thumb-down-off" {...props}></Icon>
