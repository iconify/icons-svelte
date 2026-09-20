<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3-k29i5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3-k29i5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:switch" {...props}></Icon>
