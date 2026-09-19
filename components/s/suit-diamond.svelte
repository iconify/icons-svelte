<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk3eon_gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fk3eon_gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:suit-diamond" {...props}></Icon>
