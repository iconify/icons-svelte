<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s49v1cqka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s49v1cqka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:test-js" {...props}></Icon>
