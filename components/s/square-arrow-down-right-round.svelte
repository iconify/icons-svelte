<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iajds0bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iajds0bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-arrow-down-right-round" {...props}></Icon>
