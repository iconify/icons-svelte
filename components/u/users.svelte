<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh7s0061t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qh7s0061t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:users" {...props}></Icon>
