<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hub5-1bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hub5-1bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:trending-up" {...props}></Icon>
