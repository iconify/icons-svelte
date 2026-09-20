<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glz3j1b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="glz3j1b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:volume-down-solid" {...props}></Icon>
