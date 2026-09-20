<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvxce2hwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hvxce2hwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:taxi" {...props}></Icon>
