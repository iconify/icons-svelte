<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh8b90bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oh8b90bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sonobarr-light" {...props}></Icon>
