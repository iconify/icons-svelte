<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/murjnlnua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="murjnlnua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-more-horizontal-sharp-fill" {...props}></Icon>
