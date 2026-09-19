<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvrle7lfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hvrle7lfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:wasi" {...props}></Icon>
