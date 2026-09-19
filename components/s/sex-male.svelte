<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3bhmacip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="x3bhmacip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:sex-male" {...props}></Icon>
