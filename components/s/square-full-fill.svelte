<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zse8x-bhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zse8x-bhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-full-fill" {...props}></Icon>
