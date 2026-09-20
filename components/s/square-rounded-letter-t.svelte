<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxvrt1bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxvrt1bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-t" {...props}></Icon>
