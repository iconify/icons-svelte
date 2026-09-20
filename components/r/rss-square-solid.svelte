<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x388a-7-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x388a-7-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:rss-square-solid" {...props}></Icon>
