<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvio13bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvio13bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:waves-outline" {...props}></Icon>
