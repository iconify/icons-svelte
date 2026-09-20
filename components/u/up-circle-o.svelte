<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kespyqbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kespyqbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:up-circle-o" {...props}></Icon>
