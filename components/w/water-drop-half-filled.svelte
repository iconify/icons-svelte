<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk99llbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk99llbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:water-drop-half-filled" {...props}></Icon>
