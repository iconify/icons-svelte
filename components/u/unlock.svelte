<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpgurpf1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="hpgurpf1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:unlock" {...props}></Icon>
