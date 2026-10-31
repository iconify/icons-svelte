<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcyi-ivnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcyi-ivnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:thermometer-fill-round" {...props}></Icon>
