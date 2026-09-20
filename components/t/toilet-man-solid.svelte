<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un9t5sbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="un9t5sbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:toilet-man-solid" {...props}></Icon>
