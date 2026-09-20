<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcpa5tpzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vcpa5tpzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:speaker" {...props}></Icon>
