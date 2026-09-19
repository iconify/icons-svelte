<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdj0r9j_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sdj0r9j_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:the-mighty" {...props}></Icon>
