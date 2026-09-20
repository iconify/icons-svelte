<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx3_xqbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jx3_xqbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:wave-signal-flat" {...props}></Icon>
