<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w66fu9bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w66fu9bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tower-fan" {...props}></Icon>
