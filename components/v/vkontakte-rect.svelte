<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh55srbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="kh55srbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:vkontakte-rect" {...props}></Icon>
