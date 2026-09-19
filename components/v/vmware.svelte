<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmf0blbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qmf0blbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:vmware" {...props}></Icon>
