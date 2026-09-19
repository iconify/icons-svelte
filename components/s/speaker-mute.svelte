<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q97m5m7xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q97m5m7xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:speaker-mute" {...props}></Icon>
