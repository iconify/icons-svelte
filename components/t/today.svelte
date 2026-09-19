<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqh5eqr2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="iqh5eqr2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:today" {...props}></Icon>
