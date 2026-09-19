<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq71x92eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jq71x92eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:speaker-deck" {...props}></Icon>
