<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt4xygbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xt4xygbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:zcool-logo-1-block" {...props}></Icon>
