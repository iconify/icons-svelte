<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1cfadb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1cfadb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:scan-text" {...props}></Icon>
