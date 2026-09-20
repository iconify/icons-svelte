<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uft4gr4ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uft4gr4ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:the-north-face" {...props}></Icon>
