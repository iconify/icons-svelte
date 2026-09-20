<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz0s2ac1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kz0s2ac1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sencho-dark" {...props}></Icon>
