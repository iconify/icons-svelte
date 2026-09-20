<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it4il9byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it4il9byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tidb" {...props}></Icon>
