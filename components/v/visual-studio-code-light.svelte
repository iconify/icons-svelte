<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea87w3l9f.css';
import '../../css/a/a59njwb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ea87w3l9f"/><path class="a59njwb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visual-studio-code-light" {...props}></Icon>
