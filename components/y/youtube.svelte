<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjeyw5bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":488};
const content = `<path class="fjeyw5bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:youtube" {...props}></Icon>
