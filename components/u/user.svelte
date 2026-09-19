<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi0ggj54w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vi0ggj54w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user" {...props}></Icon>
