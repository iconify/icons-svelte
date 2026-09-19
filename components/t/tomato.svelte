<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6v_4mx_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h6v_4mx_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:tomato" {...props}></Icon>
