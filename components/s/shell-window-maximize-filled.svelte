<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwrj1ekre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dwrj1ekre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:shell-window-maximize-filled" {...props}></Icon>
