<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilebc_bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilebc_bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:shield-slash" {...props}></Icon>
