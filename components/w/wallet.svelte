<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dute4tn_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dute4tn_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:wallet" {...props}></Icon>
