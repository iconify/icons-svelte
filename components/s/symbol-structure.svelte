<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn6b2sb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cn6b2sb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-structure" {...props}></Icon>
