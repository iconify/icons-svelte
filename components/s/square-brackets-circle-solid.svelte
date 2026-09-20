<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j51zypbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j51zypbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:square-brackets-circle-solid" {...props}></Icon>
