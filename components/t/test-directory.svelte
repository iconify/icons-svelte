<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pme5qfb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pme5qfb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:test-directory" {...props}></Icon>
