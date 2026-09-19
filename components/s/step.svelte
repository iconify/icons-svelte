<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo794vv7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lo794vv7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:step" {...props}></Icon>
