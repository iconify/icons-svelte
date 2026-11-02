<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzwbodb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzwbodb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-star-fill" {...props}></Icon>
