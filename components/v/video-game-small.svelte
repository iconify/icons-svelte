<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to43pubzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="to43pubzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:video-game-small" {...props}></Icon>
