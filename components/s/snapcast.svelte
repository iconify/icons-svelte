<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp_h_acca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp_h_acca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:snapcast" {...props}></Icon>
