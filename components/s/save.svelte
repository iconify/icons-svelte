<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt0yw-b-f.css';
import '../../css/j/j6fm-zcrt.css';
import '../../css/p/pacun0b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k zt0yw-b-f"/><path class="j6fm-zcrt wm-a"/><path class="pacun0b5f wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:save" {...props}></Icon>
