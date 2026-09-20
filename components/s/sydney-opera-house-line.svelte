<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf86hnbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf86hnbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sydney-opera-house-line" {...props}></Icon>
