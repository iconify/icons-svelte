<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf2_ehdun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jf2_ehdun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:thumbdown" {...props}></Icon>
