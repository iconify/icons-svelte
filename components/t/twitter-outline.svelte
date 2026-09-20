<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzz6lvbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kzz6lvbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:twitter-outline" {...props}></Icon>
