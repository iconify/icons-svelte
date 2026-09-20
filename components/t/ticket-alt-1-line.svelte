<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqm0ehbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqm0ehbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ticket-alt-1-line" {...props}></Icon>
