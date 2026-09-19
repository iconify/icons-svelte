<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/addk9z6wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="addk9z6wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:t-v-monitor-selected" {...props}></Icon>
