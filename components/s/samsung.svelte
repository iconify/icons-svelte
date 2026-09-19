<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_ix7sbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_ix7sbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:samsung" {...props}></Icon>
