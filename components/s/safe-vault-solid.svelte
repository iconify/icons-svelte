<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcck_hbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mcck_hbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:safe-vault-solid" {...props}></Icon>
