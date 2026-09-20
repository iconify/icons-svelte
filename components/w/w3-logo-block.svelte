<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hho5p9bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hho5p9bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:w3-logo-block" {...props}></Icon>
