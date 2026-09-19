<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd48b3bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cd48b3bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:tablet-landscape" {...props}></Icon>
