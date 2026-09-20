<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bocc0t2az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bocc0t2az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:scheme" {...props}></Icon>
