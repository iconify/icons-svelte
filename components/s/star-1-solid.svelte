<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-5g7ib6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b-5g7ib6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:star-1-solid" {...props}></Icon>
