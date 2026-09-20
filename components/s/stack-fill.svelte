<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdn-cbc-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdn-cbc-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stack-fill" {...props}></Icon>
