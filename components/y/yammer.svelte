<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9kk59e6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9kk59e6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:yammer" {...props}></Icon>
