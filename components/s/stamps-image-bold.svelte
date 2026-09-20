<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2hvsnj5w.css';
import '../../css/k/k55q6hbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2hvsnj5w"/><path class="k55q6hbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:stamps-image-bold" {...props}></Icon>
