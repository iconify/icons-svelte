<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a21g7ybtt.css';
import '../../css/o/ogc9qccuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a21g7ybtt"/><path class="ogc9qccuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:u3" {...props}></Icon>
