<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6g0-4b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v6g0-4b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xubuntu-dark" {...props}></Icon>
