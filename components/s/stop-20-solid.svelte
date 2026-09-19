<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfkeo8igu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wfkeo8igu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:stop-20-solid" {...props}></Icon>
