<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu7iv3gez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nu7iv3gez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-data-types" {...props}></Icon>
