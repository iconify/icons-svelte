<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1t6ehbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s1t6ehbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:zodiac-8-flat" {...props}></Icon>
