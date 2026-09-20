<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqpg00fgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqpg00fgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rupee-diamond-solid" {...props}></Icon>
