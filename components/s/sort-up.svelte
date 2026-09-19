<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1flx7vsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b1flx7vsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:sort-up" {...props}></Icon>
