<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pha7npbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pha7npbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tamiya" {...props}></Icon>
