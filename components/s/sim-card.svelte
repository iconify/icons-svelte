<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbokte67o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbokte67o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:sim-card" {...props}></Icon>
