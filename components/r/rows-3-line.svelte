<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgwe686nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgwe686nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rows-3-line" {...props}></Icon>
