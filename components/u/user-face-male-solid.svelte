<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umr1td1ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="umr1td1ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:user-face-male-solid" {...props}></Icon>
