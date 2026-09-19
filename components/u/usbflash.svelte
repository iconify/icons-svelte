<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to7ezacez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="to7ezacez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:usbflash" {...props}></Icon>
