<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teyrvibbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="teyrvibbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:water-filled" {...props}></Icon>
