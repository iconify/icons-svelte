<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqbvt3vys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dqbvt3vys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:save-outline" {...props}></Icon>
