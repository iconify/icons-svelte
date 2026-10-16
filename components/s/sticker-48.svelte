<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb70seb8t.css';
import '../../css/v/vt3q5aclv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eb70seb8t"/><path class="vt3q5aclv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sticker-48" {...props}></Icon>
