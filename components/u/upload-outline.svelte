<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp81v-bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jp81v-bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:upload-outline" {...props}></Icon>
