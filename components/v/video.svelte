<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3l7hbioh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v3l7hbioh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:video" {...props}></Icon>
