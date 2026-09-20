<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzrg6vbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xzrg6vbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star-2-filled" {...props}></Icon>
