<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjd6bdbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tjd6bdbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-remove-subtract" {...props}></Icon>
