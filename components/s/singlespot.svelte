<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it9q_rbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it9q_rbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:singlespot" {...props}></Icon>
