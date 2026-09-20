<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3alqhbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":154,"height":56};
const content = `<path class="b3alqhbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wolt" {...props}></Icon>
