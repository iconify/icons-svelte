<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqvqhx1ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oqvqhx1ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:u-s-bank-light" {...props}></Icon>
