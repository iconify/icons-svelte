<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw3f1ccle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mw3f1ccle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:trophy" {...props}></Icon>
