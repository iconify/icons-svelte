<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl3djfw5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hl3djfw5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:text-style-flat" {...props}></Icon>
