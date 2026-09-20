<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btyrtkuqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btyrtkuqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:users" {...props}></Icon>
