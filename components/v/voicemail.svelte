<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk5qbeber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tk5qbeber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:voicemail" {...props}></Icon>
