<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzmwwebxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzmwwebxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:wetv-logo-block" {...props}></Icon>
