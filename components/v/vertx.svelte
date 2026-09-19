<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj_9l9bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zj_9l9bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vertx" {...props}></Icon>
