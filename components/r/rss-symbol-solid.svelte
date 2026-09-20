<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imduh9bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="imduh9bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:rss-symbol-solid" {...props}></Icon>
