<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2lf81ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n2lf81ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:sos-sign-bold" {...props}></Icon>
