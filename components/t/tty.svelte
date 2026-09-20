<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crd1z6bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="crd1z6bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:tty" {...props}></Icon>
