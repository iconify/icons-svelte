<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwxp7xb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gwxp7xb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:z-wave-js-ui-dark" {...props}></Icon>
