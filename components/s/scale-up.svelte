<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e07wxgbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="e07wxgbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:scale-up" {...props}></Icon>
