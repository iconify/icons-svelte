<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn7uv1b9z.css';
import '../../css/e/eqckd4mok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vn7uv1b9z"/><path class="eqckd4mok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:thumbsup" {...props}></Icon>
