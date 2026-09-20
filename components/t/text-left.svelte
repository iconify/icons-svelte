<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1wd0cdzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x1wd0cdzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:text-left" {...props}></Icon>
