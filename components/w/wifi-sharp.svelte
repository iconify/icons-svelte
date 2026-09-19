<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_f7a-bya.css';
import '../../css/f/fyzd6vw5z.css';
import '../../css/r/r16hmzbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="e_f7a-bya"/><path clip-rule="evenodd" class="fyzd6vw5z"/><path clip-rule="evenodd" class="r16hmzbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:wifi-sharp" {...props}></Icon>
