<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdp-74bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mdp-74bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:threat-browser-1-remix" {...props}></Icon>
