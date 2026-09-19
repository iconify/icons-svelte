<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku0u7w7xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ku0u7w7xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:sass-alt" {...props}></Icon>
