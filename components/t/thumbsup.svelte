<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huwky1bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="huwky1bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:thumbsup" {...props}></Icon>
