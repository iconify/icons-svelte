<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykv5j8bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ykv5j8bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:zodiac-4-flat" {...props}></Icon>
