<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb6_zubqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nb6_zubqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snapchat-dark" {...props}></Icon>
