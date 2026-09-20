<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmlt0ibsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="xmlt0ibsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:screen-normal" {...props}></Icon>
