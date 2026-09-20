<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf35kd9hh.css';
import '../../css/u/ui2c-mkkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="rf35kd9hh"/><path class="ui2c-mkkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:shopping-cart" {...props}></Icon>
