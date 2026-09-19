<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed4k_eb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed4k_eb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ubiquiti-usg-p3" {...props}></Icon>
