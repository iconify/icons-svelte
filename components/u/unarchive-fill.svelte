<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7a0z09jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7a0z09jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:unarchive-fill" {...props}></Icon>
