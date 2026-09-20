<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdg34bbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gdg34bbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sd-card" {...props}></Icon>
