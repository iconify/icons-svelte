<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymbcvd2tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ymbcvd2tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spip" {...props}></Icon>
