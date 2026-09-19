<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmik2abzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kmik2abzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:whatsapp" {...props}></Icon>
