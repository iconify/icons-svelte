<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwznl150m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zwznl150m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:surface-left-filled" {...props}></Icon>
