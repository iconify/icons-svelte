<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcfp05mmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":472};
const content = `<path class="lcfp05mmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:sound-level-one" {...props}></Icon>
