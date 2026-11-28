<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz_9l1y1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz_9l1y1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tabs-x" {...props}></Icon>
