<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/firvvsbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="firvvsbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stripe-logo" {...props}></Icon>
