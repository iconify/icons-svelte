<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukbw_o16s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ukbw_o16s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:skypeaway" {...props}></Icon>
