<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v53uzibxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v53uzibxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:unspash-logo" {...props}></Icon>
