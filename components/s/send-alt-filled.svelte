<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu9u31ebu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xu9u31ebu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:send-alt-filled" {...props}></Icon>
