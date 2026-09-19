<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh51pcbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="mh51pcbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:tablet" {...props}></Icon>
