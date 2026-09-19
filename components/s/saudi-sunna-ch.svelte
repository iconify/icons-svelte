<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaib1ovzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kaib1ovzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:saudi-sunna-ch" {...props}></Icon>
