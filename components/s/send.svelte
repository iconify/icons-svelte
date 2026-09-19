<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syn093bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="syn093bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:send" {...props}></Icon>
