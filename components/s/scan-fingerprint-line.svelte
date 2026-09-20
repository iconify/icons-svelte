<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-z6sk0ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-z6sk0ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:scan-fingerprint-line" {...props}></Icon>
