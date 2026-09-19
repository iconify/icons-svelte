<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm-9bbu2i.css';
import '../../css/w/wqk418y-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm-9bbu2i"/><path class="wqk418y-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ticket" {...props}></Icon>
