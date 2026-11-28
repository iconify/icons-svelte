<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac3zu_bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac3zu_bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wand-solid" {...props}></Icon>
