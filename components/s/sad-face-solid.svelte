<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci7n6uvkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ci7n6uvkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sad-face-solid" {...props}></Icon>
