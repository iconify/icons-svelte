<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kib3_7b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kib3_7b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:scissors-outline" {...props}></Icon>
