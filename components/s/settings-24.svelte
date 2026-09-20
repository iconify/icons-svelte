<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdtx07bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdtx07bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:settings-24" {...props}></Icon>
