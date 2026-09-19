<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iufw5rweh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iufw5rweh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:temple-door" {...props}></Icon>
