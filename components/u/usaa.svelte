<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hds94nbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hds94nbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:usaa" {...props}></Icon>
