<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emhy2jo_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="emhy2jo_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yourls-dark" {...props}></Icon>
