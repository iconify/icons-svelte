<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoou20b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoou20b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:snapchat-ghost" {...props}></Icon>
