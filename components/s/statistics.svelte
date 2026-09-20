<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh3x8-bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="wh3x8-bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:statistics" {...props}></Icon>
