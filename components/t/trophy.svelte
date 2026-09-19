<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn5yx0u5x.css';
import '../../css/j/jj9yknbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="gn5yx0u5x"/><path class="jj9yknbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:trophy" {...props}></Icon>
