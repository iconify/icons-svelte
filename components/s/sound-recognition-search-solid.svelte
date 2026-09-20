<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bykfut8oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bykfut8oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:sound-recognition-search-solid" {...props}></Icon>
