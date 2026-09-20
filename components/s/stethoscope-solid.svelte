<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te73lab3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="te73lab3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:stethoscope-solid" {...props}></Icon>
