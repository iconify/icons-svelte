<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amhd8z8lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="amhd8z8lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tara" {...props}></Icon>
