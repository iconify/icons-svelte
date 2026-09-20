<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsh-0cd-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hsh-0cd-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wide-rectangle-outline" {...props}></Icon>
