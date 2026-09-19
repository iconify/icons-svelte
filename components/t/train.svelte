<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk0zd1b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="bk0zd1b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:train" {...props}></Icon>
