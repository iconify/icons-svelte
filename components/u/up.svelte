<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5yo40bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":7};
const content = `<path class="o5yo40bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:up" {...props}></Icon>
