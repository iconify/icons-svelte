<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr2xvxbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yr2xvxbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-manual" {...props}></Icon>
