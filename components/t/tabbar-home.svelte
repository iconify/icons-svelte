<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in3_skq_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in3_skq_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tabbar-home" {...props}></Icon>
