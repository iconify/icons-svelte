<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkb3nuooz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vkb3nuooz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:when-i-work" {...props}></Icon>
