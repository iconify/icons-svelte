<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0-ehhb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d0-ehhb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tram-fill" {...props}></Icon>
