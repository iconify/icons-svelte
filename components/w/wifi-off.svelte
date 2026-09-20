<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peajbfjwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="peajbfjwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wifi-off" {...props}></Icon>
