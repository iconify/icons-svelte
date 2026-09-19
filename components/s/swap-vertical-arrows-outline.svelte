<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9rze1izo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="a9rze1izo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:swap-vertical-arrows-outline" {...props}></Icon>
