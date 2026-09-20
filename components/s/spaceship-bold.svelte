<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrnak2bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xrnak2bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:spaceship-bold" {...props}></Icon>
