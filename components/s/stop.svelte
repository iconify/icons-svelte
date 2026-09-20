<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx7qfvbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="lx7qfvbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:stop" {...props}></Icon>
