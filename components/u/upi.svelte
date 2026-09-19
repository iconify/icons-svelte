<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gupyo-9yt.css';
import '../../css/l/li2ndrlth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gupyo-9yt"/><path class="li2ndrlth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:upi" {...props}></Icon>
