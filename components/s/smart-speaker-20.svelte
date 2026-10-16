<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbnqjxbpf.css';
import '../../css/r/rv6abjb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xbnqjxbpf"/><path class="rv6abjb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-speaker-20" {...props}></Icon>
