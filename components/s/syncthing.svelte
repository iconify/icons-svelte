<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqvnl9brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqvnl9brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:syncthing" {...props}></Icon>
