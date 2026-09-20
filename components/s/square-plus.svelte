<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va41csvvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="va41csvvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-plus" {...props}></Icon>
