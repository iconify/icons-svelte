<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9_p7v3fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b9_p7v3fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:scan-alt" {...props}></Icon>
