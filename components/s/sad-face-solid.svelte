<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkms7-b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gkms7-b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:sad-face-solid" {...props}></Icon>
