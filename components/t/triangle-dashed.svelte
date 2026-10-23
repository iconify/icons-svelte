<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh2ocvbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh2ocvbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:triangle-dashed" {...props}></Icon>
