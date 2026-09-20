<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioza19b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioza19b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-number-8-filled" {...props}></Icon>
