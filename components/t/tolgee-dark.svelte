<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqi5kl59o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tqi5kl59o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tolgee-dark" {...props}></Icon>
