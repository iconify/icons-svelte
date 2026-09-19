<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbnphpbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tbnphpbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-percent-fill" {...props}></Icon>
