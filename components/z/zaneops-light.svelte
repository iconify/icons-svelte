<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9x2d9xjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v9x2d9xjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zaneops-light" {...props}></Icon>
