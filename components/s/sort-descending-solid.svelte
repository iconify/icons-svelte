<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zho1kaciy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zho1kaciy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sort-descending-solid" {...props}></Icon>
