<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fit-5cnqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="fit-5cnqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:volumeup" {...props}></Icon>
