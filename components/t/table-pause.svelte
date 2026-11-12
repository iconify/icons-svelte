<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd1yz58og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd1yz58og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:table-pause" {...props}></Icon>
