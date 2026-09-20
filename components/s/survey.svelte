<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs37-c-kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="qs37-c-kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:survey" {...props}></Icon>
