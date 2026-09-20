<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgcrxl56t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lgcrxl56t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-u-turn-left-fill" {...props}></Icon>
