<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/app7u2h4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="app7u2h4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sunset" {...props}></Icon>
