<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij30-_bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij30-_bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:volume-x" {...props}></Icon>
