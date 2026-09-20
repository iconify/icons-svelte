<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnmxq6bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dnmxq6bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:user-face-id-mask-solid" {...props}></Icon>
