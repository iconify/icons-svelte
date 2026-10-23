<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woo5_fmvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woo5_fmvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:sailboat" {...props}></Icon>
