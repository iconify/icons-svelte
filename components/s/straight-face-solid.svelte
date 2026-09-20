<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmwf4sbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gmwf4sbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:straight-face-solid" {...props}></Icon>
