<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9nmr3btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v9nmr3btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:startup-remix" {...props}></Icon>
