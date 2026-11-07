<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9tzwj7ok.css';
import '../../css/b/bzy5eobti.css';
import '../../css/n/nbozb93jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9tzwj7ok"/><path class="bzy5eobti"/><path clip-rule="evenodd" class="nbozb93jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-underline-cross-outline" {...props}></Icon>
