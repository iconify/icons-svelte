<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5d7qozrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="w5d7qozrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarefour" {...props}></Icon>
