<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5t73gbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5t73gbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:writing-off" {...props}></Icon>
