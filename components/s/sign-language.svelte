<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1twksb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i1twksb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:sign-language" {...props}></Icon>
