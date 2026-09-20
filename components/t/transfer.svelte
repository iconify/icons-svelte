<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vry1uwwsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vry1uwwsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:transfer" {...props}></Icon>
