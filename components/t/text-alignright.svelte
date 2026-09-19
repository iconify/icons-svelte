<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8fymnbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="g8fymnbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:text-alignright" {...props}></Icon>
