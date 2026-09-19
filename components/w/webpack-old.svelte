<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9rnf9u2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":450,"height":512};
const content = `<path class="m9rnf9u2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:webpack-old" {...props}></Icon>
