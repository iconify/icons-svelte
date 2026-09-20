<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5_zc8bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z5_zc8bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:take-off-solid" {...props}></Icon>
