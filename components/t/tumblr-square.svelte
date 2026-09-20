<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_2eiab_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o_2eiab_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tumblr-square" {...props}></Icon>
