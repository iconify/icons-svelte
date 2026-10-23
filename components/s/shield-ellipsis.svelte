<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x59o8wbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x59o8wbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shield-ellipsis" {...props}></Icon>
