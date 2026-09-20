<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-kg8npvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o-kg8npvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:webcam-video" {...props}></Icon>
