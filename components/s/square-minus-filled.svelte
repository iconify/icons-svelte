<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pht7-hqwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pht7-hqwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-minus-filled" {...props}></Icon>
