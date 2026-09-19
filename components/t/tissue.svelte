<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8wi2c12y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h8wi2c12y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:tissue" {...props}></Icon>
