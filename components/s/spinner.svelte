<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1nk26b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1344};
const content = `<path class="n1nk26b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:spinner" {...props}></Icon>
