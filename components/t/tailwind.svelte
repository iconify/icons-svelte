<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s97w4ndbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s97w4ndbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:tailwind" {...props}></Icon>
