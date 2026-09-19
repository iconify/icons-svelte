<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyfd32boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eyfd32boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:water" {...props}></Icon>
