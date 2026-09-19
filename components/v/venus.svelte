<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by0hihb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":288,"height":512};
const content = `<path class="by0hihb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:venus" {...props}></Icon>
