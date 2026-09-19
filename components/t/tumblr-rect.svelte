<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byz7bnbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="byz7bnbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:tumblr-rect" {...props}></Icon>
