<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiscdprtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kiscdprtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:skip-forward" {...props}></Icon>
