<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8gytzbiv.css';
import '../../css/n/nigc12pwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="g8gytzbiv"/><path class="nigc12pwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:syncpack" {...props}></Icon>
