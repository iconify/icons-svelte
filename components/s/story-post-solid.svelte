<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlo3ubbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jlo3ubbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:story-post-solid" {...props}></Icon>
