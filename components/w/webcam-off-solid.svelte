<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sra7u5brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sra7u5brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:webcam-off-solid" {...props}></Icon>
