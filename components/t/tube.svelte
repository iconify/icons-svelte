<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm0s3htrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm0s3htrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:tube" {...props}></Icon>
