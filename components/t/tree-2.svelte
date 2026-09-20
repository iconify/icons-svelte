<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeat3sbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="eeat3sbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:tree-2" {...props}></Icon>
