<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0yqlr_ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b0yqlr_ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:route-filled" {...props}></Icon>
