<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg8495bbv.css';
import '../../css/z/zdj1fdckx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg8495bbv"/><path clip-rule="evenodd" class="zdj1fdckx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:unstructured" {...props}></Icon>
