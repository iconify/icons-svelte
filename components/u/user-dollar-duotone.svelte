<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow15xdb1e.css';
import '../../css/p/p5f87vboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ow15xdb1e"/><path class="p5f87vboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-dollar-duotone" {...props}></Icon>
