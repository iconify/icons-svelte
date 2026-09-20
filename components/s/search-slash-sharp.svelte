<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd8mfmbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd8mfmbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-slash-sharp" {...props}></Icon>
