<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zimsi6b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zimsi6b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:scan-2-fill" {...props}></Icon>
