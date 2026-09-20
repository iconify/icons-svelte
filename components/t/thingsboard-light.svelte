<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgow5u3ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mgow5u3ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:thingsboard-light" {...props}></Icon>
