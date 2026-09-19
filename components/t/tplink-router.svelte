<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbjc0y-xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbjc0y-xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tplink-router" {...props}></Icon>
