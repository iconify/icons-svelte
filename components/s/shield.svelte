<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okneeiblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="okneeiblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:shield" {...props}></Icon>
