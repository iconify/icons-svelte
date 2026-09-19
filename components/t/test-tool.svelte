<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8p62x6vn.css';
import '../../css/s/stbfr1b_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k8p62x6vn"/><path class="stbfr1b_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:test-tool" {...props}></Icon>
