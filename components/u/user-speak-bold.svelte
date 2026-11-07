<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1j9jhban.css';
import '../../css/f/f75dcf04p.css';
import '../../css/b/bxv6k7bpa.css';
import '../../css/c/c8mwtbcpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1j9jhban"/><path class="f75dcf04p"/><path class="bxv6k7bpa"/><path class="c8mwtbcpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-speak-bold" {...props}></Icon>
