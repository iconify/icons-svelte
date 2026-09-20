<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afo6habgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="afo6habgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:tag" {...props}></Icon>
