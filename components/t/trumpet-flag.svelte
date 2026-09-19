<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg3n2lbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xg3n2lbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:trumpet-flag" {...props}></Icon>
