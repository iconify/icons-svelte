<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-3cwvmmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y-3cwvmmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:skype-outline" {...props}></Icon>
