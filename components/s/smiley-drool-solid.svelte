<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un7b5bcgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="un7b5bcgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-drool-solid" {...props}></Icon>
