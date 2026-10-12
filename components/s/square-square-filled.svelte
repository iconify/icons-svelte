<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3jnswbyn.css';
import '../../css/a/afwvn4uuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3jnswbyn"/><path clip-rule="evenodd" class="afwvn4uuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-square-filled" {...props}></Icon>
