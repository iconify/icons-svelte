<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn7txxnka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":512};
const content = `<path class="vn7txxnka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:wenyan" {...props}></Icon>
