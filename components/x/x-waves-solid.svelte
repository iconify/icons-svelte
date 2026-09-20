<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxy4-fu0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxy4-fu0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:x-waves-solid" {...props}></Icon>
