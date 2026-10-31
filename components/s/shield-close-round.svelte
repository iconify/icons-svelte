<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn-6sfbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vn-6sfbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-close-round" {...props}></Icon>
