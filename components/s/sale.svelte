<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7h48wb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r7h48wb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sale" {...props}></Icon>
