<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdgx7fuwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdgx7fuwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-more-horizontal-round" {...props}></Icon>
