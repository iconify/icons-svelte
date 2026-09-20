<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mib7gib8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mib7gib8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:spell-check-solid" {...props}></Icon>
