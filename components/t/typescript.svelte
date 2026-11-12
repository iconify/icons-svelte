<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9cynrzbj.css';
import '../../css/w/w6sw46v9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f9cynrzbj"/><path class="w6sw46v9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typescript" {...props}></Icon>
