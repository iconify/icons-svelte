<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbik9_v8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbik9_v8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:spicebottle" {...props}></Icon>
