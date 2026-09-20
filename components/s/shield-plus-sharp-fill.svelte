<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlg-5xhef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vlg-5xhef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shield-plus-sharp-fill" {...props}></Icon>
