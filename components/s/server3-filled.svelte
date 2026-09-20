<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz288ab_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mz288ab_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:server3-filled" {...props}></Icon>
