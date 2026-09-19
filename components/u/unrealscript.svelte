<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niwz-lbqb.css';
import '../../css/b/buiu9ebyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="niwz-lbqb"/><path class="buiu9ebyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:unrealscript" {...props}></Icon>
