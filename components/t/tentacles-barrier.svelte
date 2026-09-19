<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glxx8vb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="glxx8vb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tentacles-barrier" {...props}></Icon>
