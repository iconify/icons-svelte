<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-mqzbcjv.css';
import '../../css/s/s1s3q_bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f-mqzbcjv"/><path class="s1s3q_bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:whistle-20" {...props}></Icon>
