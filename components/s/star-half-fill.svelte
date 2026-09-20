<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrcurac8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nrcurac8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:star-half-fill" {...props}></Icon>
