<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrkuoq-rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wrkuoq-rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:spiral-shape-solid" {...props}></Icon>
