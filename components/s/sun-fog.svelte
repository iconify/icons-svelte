<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqky-rbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqky-rbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sun-fog" {...props}></Icon>
