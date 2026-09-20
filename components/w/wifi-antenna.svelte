<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnmu2fhje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cnmu2fhje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:wifi-antenna" {...props}></Icon>
