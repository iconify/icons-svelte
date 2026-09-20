<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmxx6rzfe.css';
import '../../css/o/o53elobcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dmxx6rzfe"/><path class="o53elobcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:webhook-tester-light" {...props}></Icon>
