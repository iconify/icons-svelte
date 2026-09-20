<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4_vhgc-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4_vhgc-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:shield-bad-line" {...props}></Icon>
