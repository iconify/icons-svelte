<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irlny6bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="irlny6bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:stripe" {...props}></Icon>
