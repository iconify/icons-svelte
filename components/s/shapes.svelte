<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxoajqbth.css';
import '../../css/o/ov6bxrb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yxoajqbth"/><path class="ov6bxrb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:shapes" {...props}></Icon>
