<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj98js00o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gj98js00o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:upside-down-face-fill" {...props}></Icon>
