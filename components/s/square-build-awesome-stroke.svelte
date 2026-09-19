<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbil34b4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zbil34b4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-build-awesome-stroke" {...props}></Icon>
