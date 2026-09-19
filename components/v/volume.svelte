<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd2vlzvpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":315,"height":614};
const content = `<path class="bd2vlzvpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:volume" {...props}></Icon>
