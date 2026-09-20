<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9au01b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g9au01b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storj" {...props}></Icon>
