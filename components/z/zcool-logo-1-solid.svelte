<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npis9_bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="npis9_bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:zcool-logo-1-solid" {...props}></Icon>
