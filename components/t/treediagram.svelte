<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj-au7bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="wj-au7bqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:treediagram" {...props}></Icon>
