<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxc-g272t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxc-g272t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:view-dashboard" {...props}></Icon>
