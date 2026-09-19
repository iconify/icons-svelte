<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4nua5brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4nua5brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tesla-open" {...props}></Icon>
