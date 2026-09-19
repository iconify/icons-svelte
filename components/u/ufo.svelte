<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyjeihbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":448};
const content = `<path class="kyjeihbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:ufo" {...props}></Icon>
