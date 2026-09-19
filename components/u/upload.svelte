<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6mep9bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r6mep9bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:upload" {...props}></Icon>
