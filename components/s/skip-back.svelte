<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tri6pru9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tri6pru9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:skip-back" {...props}></Icon>
