<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm7lsubwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nm7lsubwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:severity-unknown" {...props}></Icon>
