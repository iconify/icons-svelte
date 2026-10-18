<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsfp_ybjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsfp_ybjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-cog" {...props}></Icon>
