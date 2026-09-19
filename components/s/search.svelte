<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2wqe5ssz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="v2wqe5ssz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:search" {...props}></Icon>
