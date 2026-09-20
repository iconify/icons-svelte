<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nln509zzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nln509zzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:speedtest-tracker-dark" {...props}></Icon>
