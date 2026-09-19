<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqo-pdbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqo-pdbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sale-alt-filled" {...props}></Icon>
