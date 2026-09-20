<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3v-074nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3v-074nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:soccer-field" {...props}></Icon>
