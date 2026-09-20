<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6l_u-bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6l_u-bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-align-offset-left-sharp-fill" {...props}></Icon>
