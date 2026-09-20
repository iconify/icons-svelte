<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj9jdebvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qj9jdebvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:vray-logo-block" {...props}></Icon>
