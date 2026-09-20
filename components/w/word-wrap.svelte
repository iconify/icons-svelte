<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzg8c0oxb.css';
import '../../css/o/ozx0m_bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kzg8c0oxb"/><path class="ozx0m_bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:word-wrap" {...props}></Icon>
