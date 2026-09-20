<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knz2nkbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="knz2nkbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:shield-check-filled" {...props}></Icon>
