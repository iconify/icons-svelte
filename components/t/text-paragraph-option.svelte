<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9r-seisg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="a9r-seisg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:text-paragraph-option" {...props}></Icon>
