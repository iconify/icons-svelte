<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztfwjikic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztfwjikic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:watch-device" {...props}></Icon>
