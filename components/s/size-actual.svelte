<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de-x6ubrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="de-x6ubrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:size-actual" {...props}></Icon>
