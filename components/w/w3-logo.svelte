<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glz0julzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glz0julzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:w3-logo" {...props}></Icon>
