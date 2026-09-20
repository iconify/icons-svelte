<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6_pbfbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a6_pbfbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-settings-filled" {...props}></Icon>
