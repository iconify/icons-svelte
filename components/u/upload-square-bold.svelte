<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzl_0yb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mzl_0yb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:upload-square-bold" {...props}></Icon>
