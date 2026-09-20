<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k23dc3bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k23dc3bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shark-fin-outline" {...props}></Icon>
