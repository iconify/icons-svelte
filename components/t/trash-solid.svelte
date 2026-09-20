<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-5b-ibab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z-5b-ibab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:trash-solid" {...props}></Icon>
