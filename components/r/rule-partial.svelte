<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciqspz6bd.css';
import '../../css/v/v_ge03b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ciqspz6bd"/><path class="v_ge03b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rule-partial" {...props}></Icon>
