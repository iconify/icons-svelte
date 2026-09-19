<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orgn1ubrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="orgn1ubrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:tray-calendar-26" {...props}></Icon>
