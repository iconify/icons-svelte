<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7cxk4byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s7cxk4byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:workspace-untrusted" {...props}></Icon>
