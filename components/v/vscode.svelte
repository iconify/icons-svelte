<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm2vspb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mm2vspb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:vscode" {...props}></Icon>
