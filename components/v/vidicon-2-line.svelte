<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k91r18brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k91r18brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:vidicon-2-line" {...props}></Icon>
