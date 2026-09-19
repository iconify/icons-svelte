<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7f4pj88b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c7f4pj88b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:v8-turbofan" {...props}></Icon>
