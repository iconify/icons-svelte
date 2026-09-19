<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df0e-4b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="df0e-4b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:th" {...props}></Icon>
