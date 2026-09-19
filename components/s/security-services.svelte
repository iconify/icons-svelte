<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aik43r5pi.css';
import '../../css/j/jvytmhb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aik43r5pi"/><path class="jvytmhb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:security-services" {...props}></Icon>
