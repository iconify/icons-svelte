<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imkf5vvcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="imkf5vvcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:teddycloud-light" {...props}></Icon>
