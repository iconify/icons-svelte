<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqhu_g8oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zqhu_g8oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:triangle-left" {...props}></Icon>
