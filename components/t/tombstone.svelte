<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al-4-0btz.css';
import '../../css/t/twbohlb9d.css';
import '../../css/l/l9h-wybvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al-4-0btz wm-k"/><path class="twbohlb9d wm-a"/><path class="l9h-wybvf wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:tombstone" {...props}></Icon>
