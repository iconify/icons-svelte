<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxvm15b7r.css';
import '../../css/j/jq2vx7i2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xxvm15b7r"/><path class="jq2vx7i2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:word-cloud" {...props}></Icon>
