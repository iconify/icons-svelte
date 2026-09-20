<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v05r4ubzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v05r4ubzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sticky-note-minus" {...props}></Icon>
