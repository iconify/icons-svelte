<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvvujxbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lvvujxbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:speech-bubble-lightning-bolt-fill-16" {...props}></Icon>
