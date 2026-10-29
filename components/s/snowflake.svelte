<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjf5pubej.css';
import '../../css/k/kzt1twblh.css';
import '../../css/x/xbxbwdb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjf5pubej"/><path class="kzt1twblh"/><path class="xbxbwdb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:snowflake" {...props}></Icon>
