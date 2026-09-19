<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8_ggj7jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a8_ggj7jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:sage" {...props}></Icon>
