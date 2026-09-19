<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7lrwob-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="d7lrwob-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:wiley-square" {...props}></Icon>
