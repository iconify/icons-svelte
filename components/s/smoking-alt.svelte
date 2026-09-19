<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5duaqbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1344};
const content = `<path class="b5duaqbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:smoking-alt" {...props}></Icon>
