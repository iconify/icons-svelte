<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gei358h8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gei358h8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unimus-dark" {...props}></Icon>
