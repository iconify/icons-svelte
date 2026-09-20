<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz05-gtnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bz05-gtnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-field" {...props}></Icon>
