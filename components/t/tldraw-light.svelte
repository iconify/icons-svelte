<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to4xgtbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to4xgtbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:tldraw-light" {...props}></Icon>
