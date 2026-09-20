<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfiq4lbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfiq4lbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:walmart" {...props}></Icon>
