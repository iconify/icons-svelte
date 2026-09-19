<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccqy6rbku.css';
import '../../css/v/vvwnsy9um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="ccqy6rbku"/><path class="vvwnsy9um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:visual-recognition" {...props}></Icon>
