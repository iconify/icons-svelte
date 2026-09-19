<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m14r7jbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="m14r7jbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:snow" {...props}></Icon>
