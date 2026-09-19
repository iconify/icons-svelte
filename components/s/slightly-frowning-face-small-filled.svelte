<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv_pyhgkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="uv_pyhgkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:slightly-frowning-face-small-filled" {...props}></Icon>
