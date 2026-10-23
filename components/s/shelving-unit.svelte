<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykdntwb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykdntwb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shelving-unit" {...props}></Icon>
