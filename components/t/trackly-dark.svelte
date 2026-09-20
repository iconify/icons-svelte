<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx-rucm_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hx-rucm_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trackly-dark" {...props}></Icon>
