<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7iavyh8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x7iavyh8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wizarr-dark" {...props}></Icon>
