<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9frzpbrc.css';
import '../../css/m/mtcvrxbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z9frzpbrc"/><path class="mtcvrxbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:video-48" {...props}></Icon>
