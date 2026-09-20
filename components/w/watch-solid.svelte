<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ody6ekxva.css';
import '../../css/m/msx52gb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ody6ekxva"/><path class="msx52gb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:watch-solid" {...props}></Icon>
