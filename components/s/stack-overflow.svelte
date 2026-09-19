<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7eat9bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="k7eat9bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:stack-overflow" {...props}></Icon>
