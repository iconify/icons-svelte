<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny7m4gbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":18};
const content = `<path class="ny7m4gbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:select-all" {...props}></Icon>
