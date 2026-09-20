<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl74mdkao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="dl74mdkao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:stackoverflow-solid" {...props}></Icon>
