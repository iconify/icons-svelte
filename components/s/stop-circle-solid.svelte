<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm7b_gbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="sm7b_gbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:stop-circle-solid" {...props}></Icon>
