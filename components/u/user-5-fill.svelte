<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mugmvobcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mugmvobcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-5-fill" {...props}></Icon>
