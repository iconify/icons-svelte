<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai-0czjuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ai-0czjuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:xcode" {...props}></Icon>
