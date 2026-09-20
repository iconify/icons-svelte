<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae433abpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ae433abpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:send-visee-light" {...props}></Icon>
